<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w6rjw2b9s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="w6rjw2b9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:arrow-bottom-left" /></template>
