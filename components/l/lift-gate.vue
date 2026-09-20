<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n_7_dpb7r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="n_7_dpb7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:lift-gate" /></template>
