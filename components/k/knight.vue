<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2e5gzblx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":769,"height":1024};
const content = `<path class="d2e5gzblx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:knight" /></template>
