<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ggdejnbbs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ggdejnbbs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:justify" /></template>
