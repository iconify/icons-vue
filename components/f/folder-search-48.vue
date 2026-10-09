<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bwypsp5ub.css';
import '../../css/g/g14r5ubhu.css';
import '../../css/d/dexi_790w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bwypsp5ub"/><path class="g14r5ubhu"/><path class="dexi_790w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:folder-search-48" /></template>
