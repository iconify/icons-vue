<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wa-2tbcpa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="wa-2tbcpa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:laundry" /></template>
