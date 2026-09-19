<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h8t72pbdn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="h8t72pbdn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:circle-slash-compact" /></template>
