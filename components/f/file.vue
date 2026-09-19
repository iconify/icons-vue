<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s4ey6x3to.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1792};
const content = `<path class="s4ey6x3to"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:file" /></template>
