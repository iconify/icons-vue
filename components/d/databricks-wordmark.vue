<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e7m4sz57z.css';
import '../../css/z/z-hzdxb8f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="e7m4sz57z"/><path class="z-hzdxb8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:databricks-wordmark" /></template>
