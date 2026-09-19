<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d1dh8kb7i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="d1dh8kb7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:behance" /></template>
