<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9tr6bcfx.css';
import '../../css/j/jx3ay999g.css';
import '../../css/b/bolb5gbrp.css';
import '../../css/j/js09wjuez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="y9tr6bcfx"><path class="jx3ay999g"/><path class="bolb5gbrp"/><path class="js09wjuez"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:ambulance" /></template>
