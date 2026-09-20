<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e39thnbfi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="e39thnbfi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:club-chair" /></template>
