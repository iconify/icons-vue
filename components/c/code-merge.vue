<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wscmxgl4z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="wscmxgl4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:code-merge" /></template>
