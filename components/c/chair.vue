<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e3lgamtva.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":832};
const content = `<path class="e3lgamtva"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:chair" /></template>
