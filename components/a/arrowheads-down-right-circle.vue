<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zu2yisb3i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="zu2yisb3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:arrowheads-down-right-circle" /></template>
