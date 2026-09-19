<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b7tsvw0-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="b7tsvw0-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:electricity" /></template>
