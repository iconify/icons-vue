<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bc-q1h0-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bc-q1h0-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:figma" /></template>
