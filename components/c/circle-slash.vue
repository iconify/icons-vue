<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/toh0lpxph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="toh0lpxph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:circle-slash" /></template>
