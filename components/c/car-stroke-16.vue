<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jq-e9ebei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jq-e9ebei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:car-stroke-16" /></template>
