<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/y/yiynbpjky.css';
import '../../css/c/c2o4e4sms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="yiynbpjky"/><path class="c2o4e4sms"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:battery-outline" /></template>
