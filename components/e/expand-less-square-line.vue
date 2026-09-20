<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i0fec4b_v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i0fec4b_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:expand-less-square-line" /></template>
