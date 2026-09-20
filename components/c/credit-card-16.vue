<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uws-23bsl.css';
import '../../css/d/d83mplq2z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="uws-23bsl"/><path class="d83mplq2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:credit-card-16" /></template>
