<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xk7rjrwsm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="xk7rjrwsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:line-height-thin" /></template>
