<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q58c3bbto.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":257};
const content = `<path class="q58c3bbto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:claude-ai" /></template>
