<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/swtptacfg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="swtptacfg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:chevron-mini" /></template>
