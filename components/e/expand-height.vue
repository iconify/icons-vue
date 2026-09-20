<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cxahy_bxc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="cxahy_bxc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:expand-height" /></template>
