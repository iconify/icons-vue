<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ov_ok3q0l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ov_ok3q0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:dot-grid-fill" /></template>
