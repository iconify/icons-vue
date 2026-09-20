<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xvsjqhb-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="xvsjqhb-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:box-light-round-down-left" /></template>
