<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xa6q3wgpa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xa6q3wgpa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ace-stream-light" /></template>
