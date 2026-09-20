<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tyq9-yb2z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="tyq9-yb2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:list" /></template>
