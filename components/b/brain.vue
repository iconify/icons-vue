<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eikj0cfuq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eikj0cfuq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:brain" /></template>
