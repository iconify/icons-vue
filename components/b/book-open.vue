<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/himeb8x8w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="himeb8x8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:book-open" /></template>
