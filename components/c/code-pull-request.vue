<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/ju1-0mb4z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ju1-0mb4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:code-pull-request" /></template>
