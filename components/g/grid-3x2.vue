<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fcebpw6vt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fcebpw6vt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:grid-3x2" /></template>
