<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qyjlmrb5i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qyjlmrb5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:headset-sparkle-stroke-16" /></template>
