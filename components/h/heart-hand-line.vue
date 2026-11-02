<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i8_4fpbsf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i8_4fpbsf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:heart-hand-line" /></template>
