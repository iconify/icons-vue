<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jwbwk7pur.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jwbwk7pur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:cannabis" /></template>
