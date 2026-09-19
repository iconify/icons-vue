<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/benkryb_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":455,"height":735};
const content = `<path class="benkryb_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:e-upper-case" /></template>
