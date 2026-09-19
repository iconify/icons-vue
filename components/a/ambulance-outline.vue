<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ujsl2ac1k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="ujsl2ac1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:ambulance-outline" /></template>
