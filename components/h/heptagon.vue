<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cug31wb8h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="cug31wb8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:heptagon" /></template>
