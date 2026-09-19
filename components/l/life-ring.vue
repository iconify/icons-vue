<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e-19e_q6f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="e-19e_q6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-regular:life-ring" /></template>
