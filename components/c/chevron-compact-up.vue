<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pburr5brf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="pburr5brf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:chevron-compact-up" /></template>
