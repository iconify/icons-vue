<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bh3nr0brd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bh3nr0brd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:fluidd-dark" /></template>
