<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cb9hnubnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":432};
const content = `<path class="cb9hnubnd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:bluetooth-connected" /></template>
