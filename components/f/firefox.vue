<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hu5lc3b_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hu5lc3b_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:firefox" /></template>
