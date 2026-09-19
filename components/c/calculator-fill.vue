<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u34u9o27z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="u34u9o27z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:calculator-fill" /></template>
