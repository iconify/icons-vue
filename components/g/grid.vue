<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e2wijgb-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="e2wijgb-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:grid" /></template>
