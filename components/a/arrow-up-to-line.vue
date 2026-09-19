<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nt__-0brb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="nt__-0brb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:arrow-up-to-line" /></template>
