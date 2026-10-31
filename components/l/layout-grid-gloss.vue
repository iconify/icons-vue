<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t7wbwcbae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t7wbwcbae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:layout-grid-gloss" /></template>
