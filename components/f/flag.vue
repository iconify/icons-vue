<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/drstt1dzv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="drstt1dzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:flag" /></template>
