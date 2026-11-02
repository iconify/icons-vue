<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tf3_j1bgk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tf3_j1bgk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:exposure-line" /></template>
