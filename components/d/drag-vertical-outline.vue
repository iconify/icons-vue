<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/et8rym2vl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="et8rym2vl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:drag-vertical-outline" /></template>
