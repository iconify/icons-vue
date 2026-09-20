<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m2md7htxj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m2md7htxj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:explore-off" /></template>
