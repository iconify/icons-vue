<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gbmu9zd0n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="gbmu9zd0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:align-items-center-outline" /></template>
