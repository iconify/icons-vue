<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xjeyu86rc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xjeyu86rc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:chevron-down" /></template>
