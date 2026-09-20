<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m2d_n-b0h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m2d_n-b0h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:delete-3-line" /></template>
