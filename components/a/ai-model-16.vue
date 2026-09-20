<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k1k18lfcc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="k1k18lfcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:ai-model-16" /></template>
