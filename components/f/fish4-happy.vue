<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sidtoebng.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="sidtoebng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:fish4-happy" /></template>
