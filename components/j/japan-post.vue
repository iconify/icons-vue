<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l7a86-bsv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="l7a86-bsv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:japan-post" /></template>
