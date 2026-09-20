<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yz42h5tvc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="yz42h5tvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:literal-rtl" /></template>
