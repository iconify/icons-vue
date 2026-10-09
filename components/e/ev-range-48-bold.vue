<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fop36ybmj.css';
import '../../css/v/vpxwfc0bg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fop36ybmj"/><path class="vpxwfc0bg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ev-range-48-bold" /></template>
