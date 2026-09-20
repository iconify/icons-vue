<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ro28oxbjt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ro28oxbjt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:arrow-down-line" /></template>
