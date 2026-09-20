<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/djj-rrvqc.css';
import '../../css/w/w3-ezh4fh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="djj-rrvqc"/><path class="w3-ezh4fh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:left-speech-bubble" /></template>
