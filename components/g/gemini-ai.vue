<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zpbd8hs9r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zpbd8hs9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:gemini-ai" /></template>
