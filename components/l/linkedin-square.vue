<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r3voqrbze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1536};
const content = `<path class="r3voqrbze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:linkedin-square" /></template>
