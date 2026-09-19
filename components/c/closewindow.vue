<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cv23k6bep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="cv23k6bep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:closewindow" /></template>
