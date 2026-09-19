<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ubv9gybnc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="ubv9gybnc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:comment-quotes" /></template>
