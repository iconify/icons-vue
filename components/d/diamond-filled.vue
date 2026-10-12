<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e-b_8bcwz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e-b_8bcwz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:diamond-filled" /></template>
