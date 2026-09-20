<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s3n8v4ttr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="s3n8v4ttr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:books" /></template>
