<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/er_qiqwbb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="er_qiqwbb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:battery-warning-fill" /></template>
