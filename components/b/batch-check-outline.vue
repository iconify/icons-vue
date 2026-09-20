<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ofx5qsbuk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ofx5qsbuk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:batch-check-outline" /></template>
