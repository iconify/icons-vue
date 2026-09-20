<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lmm9cxber.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="lmm9cxber"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:arrow-right-16" /></template>
