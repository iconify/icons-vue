<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ofajhpoef.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ofajhpoef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:hospital-fill" /></template>
