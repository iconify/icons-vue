<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ahridsb8p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ahridsb8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:arrow-turn-down-right" /></template>
