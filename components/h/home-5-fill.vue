<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/le2wawnyp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="le2wawnyp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:home-5-fill" /></template>
