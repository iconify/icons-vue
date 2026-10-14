<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hf0dqmblf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hf0dqmblf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:conduyt-light" /></template>
