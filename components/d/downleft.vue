<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ud5onibxb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1023};
const content = `<path class="ud5onibxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:downleft" /></template>
