<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d6dtqwb-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d6dtqwb-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:book-5-fill" /></template>
