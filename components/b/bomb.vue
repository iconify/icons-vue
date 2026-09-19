<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zr5t_bc0y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zr5t_bc0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:bomb" /></template>
