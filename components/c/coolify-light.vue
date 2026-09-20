<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sonzv-b6i.css';
import '../../css/y/y41okqbrh.css';
import '../../css/e/e1nqa7bmg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sonzv-b6i"/><path class="y41okqbrh"/><path class="e1nqa7bmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:coolify-light" /></template>
