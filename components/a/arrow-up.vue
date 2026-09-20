<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lm_tybc4k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lm_tybc4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:arrow-up" /></template>
