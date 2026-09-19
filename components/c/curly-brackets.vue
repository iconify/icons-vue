<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qickg1epq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qickg1epq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:curly-brackets" /></template>
