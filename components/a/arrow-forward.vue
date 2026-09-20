<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e5q0ggb2t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e5q0ggb2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:arrow-forward" /></template>
