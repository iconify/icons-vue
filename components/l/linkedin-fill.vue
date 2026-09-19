<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h_q3dvbyq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h_q3dvbyq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:linkedin-fill" /></template>
