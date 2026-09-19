<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c610etbnx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":432};
const content = `<path class="c610etbnx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:8tracks" /></template>
