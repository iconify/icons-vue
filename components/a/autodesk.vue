<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/ssd_2ibyz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ssd_2ibyz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:autodesk" /></template>
