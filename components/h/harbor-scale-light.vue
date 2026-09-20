<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ktq9-0qkl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ktq9-0qkl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:harbor-scale-light" /></template>
