<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m49pj6bjg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="m49pj6bjg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:cloud" /></template>
