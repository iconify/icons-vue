<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e7ua0mm9f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="e7ua0mm9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:calendar-plus-solid" /></template>
