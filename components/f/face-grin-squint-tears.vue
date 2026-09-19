<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q1tpi1b0v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q1tpi1b0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-regular:face-grin-squint-tears" /></template>
