<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qzd0j5pdz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qzd0j5pdz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:circle-empty" /></template>
