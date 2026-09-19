<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dje1_sblw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="dje1_sblw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:arrows-collapse" /></template>
