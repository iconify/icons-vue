<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kgev34b0r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kgev34b0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:inventory-fill" /></template>
