<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vufhl4_du.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vufhl4_du"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:book-open-check-line" /></template>
