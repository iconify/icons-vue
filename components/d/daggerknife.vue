<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ogp3kachq.css';
import '../../css/c/ceh3nbbjr.css';
import '../../css/n/nuph4koxg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ogp3kachq"/><path class="ceh3nbbjr"/><path class="nuph4koxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:daggerknife" /></template>
