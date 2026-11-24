<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e8arqdb1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e8arqdb1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:carets-from-axis-dashed-vertical-filled" /></template>
