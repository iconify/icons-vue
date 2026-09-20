<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xnlhaj0by.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xnlhaj0by"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:arrow-up-circle-fill" /></template>
