<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jq6tgxbrf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jq6tgxbrf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:add-child-node" /></template>
