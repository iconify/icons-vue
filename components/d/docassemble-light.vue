<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sc83tyb0q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sc83tyb0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:docassemble-light" /></template>
