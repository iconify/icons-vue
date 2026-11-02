<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pqxgb6byf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pqxgb6byf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:align-vertical-distribute-center-fill" /></template>
