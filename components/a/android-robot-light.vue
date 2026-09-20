<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gjq7m9irb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gjq7m9irb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:android-robot-light" /></template>
