<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/blynalbvu.css';
import '../../css/n/n0vzj_b5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<rect class="blynalbvu"/><path class="n0vzj_b5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:lock-locked-fill-16" /></template>
