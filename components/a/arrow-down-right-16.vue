<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nf5jombhy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="nf5jombhy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:arrow-down-right-16" /></template>
