<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q9xq4ewmx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q9xq4ewmx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:draw-io" /></template>
