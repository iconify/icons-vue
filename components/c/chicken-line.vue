<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e0wpv1pbg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e0wpv1pbg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:chicken-line" /></template>
