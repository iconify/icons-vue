<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h7h00g2fi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":16};
const content = `<path class="h7h00g2fi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:file-media" /></template>
