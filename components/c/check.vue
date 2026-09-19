<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l4-ss0b8s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l4-ss0b8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:check" /></template>
