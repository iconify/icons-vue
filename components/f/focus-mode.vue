<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y0x7j6tzf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y0x7j6tzf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:focus-mode" /></template>
