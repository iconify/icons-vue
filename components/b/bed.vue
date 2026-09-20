<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t6eue1_ca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t6eue1_ca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:bed" /></template>
