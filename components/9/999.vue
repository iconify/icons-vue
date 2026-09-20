<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sa9aseb2e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="sa9aseb2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:999" /></template>
