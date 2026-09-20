<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rirhsprsm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rirhsprsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:colum-up" /></template>
