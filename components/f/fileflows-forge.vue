<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fiowh3tts.css';
import '../../css/f/flsxa_bns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fiowh3tts"/><path class="flsxa_bns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:fileflows-forge" /></template>
