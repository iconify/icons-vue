<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jwqh1bcon.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jwqh1bcon"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:check-lg" /></template>
