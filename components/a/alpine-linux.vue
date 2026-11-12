<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j1okeccbo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j1okeccbo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:alpine-linux" /></template>
