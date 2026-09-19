<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t0334b8lh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":448};
const content = `<path class="t0334b8lh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:car" /></template>
