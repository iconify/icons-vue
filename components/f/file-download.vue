<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v2n7cu74s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1280,"height":1536};
const content = `<path class="v2n7cu74s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:file-download" /></template>
