<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t403b_11h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1023};
const content = `<path class="t403b_11h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:flagtriangle" /></template>
