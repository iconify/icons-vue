<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wur_xks1v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="wur_xks1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:earth-america" /></template>
