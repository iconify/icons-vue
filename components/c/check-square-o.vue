<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t35nljbwo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="t35nljbwo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:check-square-o" /></template>
