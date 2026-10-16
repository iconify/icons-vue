<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v1u8_-b9b.css';
import '../../css/a/a_6bvzblh.css';
import '../../css/d/d32_g_rfi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="v1u8_-b9b"/><path class="a_6bvzblh"/><path class="d32_g_rfi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hydrogen-blending-48-bold" /></template>
