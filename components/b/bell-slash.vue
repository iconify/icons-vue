<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u5df93h4g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="u5df93h4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:bell-slash" /></template>
