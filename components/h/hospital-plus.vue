<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bl5q3r92p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bl5q3r92p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:hospital-plus" /></template>
