<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lqjcjh8-x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="lqjcjh8-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:exclamation" /></template>
