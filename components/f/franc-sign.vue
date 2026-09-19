<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/te59bx3dm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":320,"height":512};
const content = `<path class="te59bx3dm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:franc-sign" /></template>
