<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vz3672b7k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="vz3672b7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:comment-nodes" /></template>
