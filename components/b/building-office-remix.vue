<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y-_gtncfa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="y-_gtncfa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:building-office-remix" /></template>
