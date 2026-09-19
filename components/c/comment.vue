<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c5im1qbau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1137,"height":1000};
const content = `<path class="c5im1qbau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="websymbol:comment" /></template>
