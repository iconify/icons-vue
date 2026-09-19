<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qd5nq7b-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qd5nq7b-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:border-left" /></template>
