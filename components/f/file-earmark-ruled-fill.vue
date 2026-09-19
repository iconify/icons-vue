<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sa98zrbzw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="sa98zrbzw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:file-earmark-ruled-fill" /></template>
