<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jztg1xb4j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jztg1xb4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:chatbubble-ellipses-sharp" /></template>
