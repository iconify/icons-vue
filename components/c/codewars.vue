<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q7ptetrtf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="q7ptetrtf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:codewars" /></template>
