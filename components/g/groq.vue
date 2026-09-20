<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lg6obmb_i.css';
import '../../css/c/c_7z8eb4f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":201,"height":201};
const content = `<path class="lg6obmb_i"/><path class="c_7z8eb4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:groq" /></template>
