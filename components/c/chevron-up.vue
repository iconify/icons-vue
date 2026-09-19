<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fd180xnta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fd180xnta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="charm:chevron-up" /></template>
