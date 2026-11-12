<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dad-_9bln.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dad-_9bln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:imdb-light" /></template>
