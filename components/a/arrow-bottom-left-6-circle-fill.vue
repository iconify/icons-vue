<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o1gwhibcz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o1gwhibcz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:arrow-bottom-left-6-circle-fill" /></template>
