<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bqhnwrbfp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bqhnwrbfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-search-alt-2" /></template>
