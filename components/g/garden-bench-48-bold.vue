<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ehlerpbsz.css';
import '../../css/f/fwo9yhojg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ehlerpbsz"/><path class="fwo9yhojg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:garden-bench-48-bold" /></template>
