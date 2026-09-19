<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e2_v31b8k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e2_v31b8k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:flame-filled" /></template>
