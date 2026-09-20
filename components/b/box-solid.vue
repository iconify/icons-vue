<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qbmp6hbdx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qbmp6hbdx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:box-solid" /></template>
