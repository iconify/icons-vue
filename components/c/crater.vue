<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v9gpu_b2t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="v9gpu_b2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:crater" /></template>
