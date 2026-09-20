<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nxunvybcj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="nxunvybcj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:hd" /></template>
