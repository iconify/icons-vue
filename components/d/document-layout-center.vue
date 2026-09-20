<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j5_gilgfy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j5_gilgfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:document-layout-center" /></template>
