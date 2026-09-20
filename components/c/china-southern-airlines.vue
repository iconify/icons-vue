<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xyqi38btk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xyqi38btk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:china-southern-airlines" /></template>
