<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oro-z9kun.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="oro-z9kun"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:docmost-light" /></template>
