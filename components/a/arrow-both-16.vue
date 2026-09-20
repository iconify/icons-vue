<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/px5cveb1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="px5cveb1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:arrow-both-16" /></template>
