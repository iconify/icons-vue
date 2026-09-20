<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/esymu1zan.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="esymu1zan"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:layout-grid-2-line" /></template>
