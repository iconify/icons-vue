<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y8vnd1byk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="y8vnd1byk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:circle-nodes" /></template>
