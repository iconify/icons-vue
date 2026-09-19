<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9tr6bcfx.css';
import '../../css/a/auzy0hbwl.css';
import '../../css/i/ivargsbvq.css';
import '../../css/s/s_6zp33hf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="y9tr6bcfx"><path class="auzy0hbwl"/><path class="ivargsbvq"/><path class="s_6zp33hf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:cogs" /></template>
