<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kf0cu3pan.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kf0cu3pan"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:chevereto" /></template>
