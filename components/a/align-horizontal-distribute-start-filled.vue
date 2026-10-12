<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/foz5q4n-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="foz5q4n-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:align-horizontal-distribute-start-filled" /></template>
