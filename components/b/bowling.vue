<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eibrw93vl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eibrw93vl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-lab:bowling" /></template>
