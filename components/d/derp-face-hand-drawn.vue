<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u1630-b4j.css';
import '../../css/g/g7u0urmpu.css';
import '../../css/b/ba10csb6z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path clip-rule="evenodd" class="u1630-b4j"/><path clip-rule="evenodd" class="g7u0urmpu"/><path class="ba10csb6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-memes:derp-face-hand-drawn" /></template>
