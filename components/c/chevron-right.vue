<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/is07h1_2a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="is07h1_2a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ei:chevron-right" /></template>
