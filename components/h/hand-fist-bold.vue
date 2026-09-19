<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/df018n8xi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="df018n8xi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:hand-fist-bold" /></template>
