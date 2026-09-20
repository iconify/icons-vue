<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fxbnq1bpk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fxbnq1bpk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:heart-hand-line" /></template>
