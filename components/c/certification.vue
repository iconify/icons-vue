<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e5pk2n8fa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e5pk2n8fa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:certification" /></template>
