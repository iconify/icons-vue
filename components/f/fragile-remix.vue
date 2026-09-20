<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cjjm0f90s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="cjjm0f90s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:fragile-remix" /></template>
