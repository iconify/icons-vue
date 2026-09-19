<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pk2e3lkou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="pk2e3lkou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:editor-layout" /></template>
