<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qs2gp9asi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qs2gp9asi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:bluesky" /></template>
