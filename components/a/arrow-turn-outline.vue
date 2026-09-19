<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gz4fgyl6l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="gz4fgyl6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:arrow-turn-outline" /></template>
