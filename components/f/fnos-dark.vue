<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jvh4yw4zh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jvh4yw4zh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:fnos-dark" /></template>
