<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ex18vzb4h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ex18vzb4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:color-bucket-brush-bold" /></template>
