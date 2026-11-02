<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ke28dhbov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ke28dhbov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:earth-latitude-line" /></template>
