<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ai3gqkb8w.css';
import '../../css/e/ejk8koamo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ai3gqkb8w"/><path class="ejk8koamo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:gas-compressor-20" /></template>
