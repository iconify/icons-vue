<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c53i_1bdt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c53i_1bdt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:footer" /></template>
