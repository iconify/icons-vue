<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qoqo4lbae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qoqo4lbae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:chevron-double-right-stroke-16" /></template>
