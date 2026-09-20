<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m66ceobye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m66ceobye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:align-left-fill" /></template>
