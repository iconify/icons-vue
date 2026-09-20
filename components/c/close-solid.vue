<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pxk9lbbab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="pxk9lbbab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:close-solid" /></template>
