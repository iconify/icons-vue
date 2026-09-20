<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f3noy3bgn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f3noy3bgn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:flag-dollar" /></template>
