<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qpilv4b3p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="qpilv4b3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:emoji-happy" /></template>
