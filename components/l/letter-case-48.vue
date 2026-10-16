<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ayrqo3blg.css';
import '../../css/g/gb1sjyb5o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ayrqo3blg"/><path class="gb1sjyb5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:letter-case-48" /></template>
