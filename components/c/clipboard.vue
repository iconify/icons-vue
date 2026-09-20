<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ysm1hybax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ysm1hybax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:clipboard" /></template>
