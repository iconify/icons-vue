<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q1ngpfbyu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q1ngpfbyu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:gmail-cleaner-light" /></template>
