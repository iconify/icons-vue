<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q9v47kbel.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="q9v47kbel"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:diamond-48" /></template>
