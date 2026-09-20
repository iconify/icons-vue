<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kr3xfyraj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="kr3xfyraj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:j" /></template>
