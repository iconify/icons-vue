<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d8j3nlb0n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d8j3nlb0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:git" /></template>
