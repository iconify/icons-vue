<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ds199pbjz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ds199pbjz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:arrow-top-right" /></template>
