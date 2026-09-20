<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kucpko94k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="kucpko94k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:arrowheads-up-chevron-circle" /></template>
