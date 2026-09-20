<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/grd3ttq0e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="grd3ttq0e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:head-side-cough" /></template>
