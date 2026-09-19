<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9tr6bcfx.css';
import '../../css/z/z2aue9bmq.css';
import '../../css/s/szqd1bcxc.css';
import '../../css/l/lxivd679c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="y9tr6bcfx"><path class="z2aue9bmq"/><path class="szqd1bcxc"/><path class="lxivd679c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:lips" /></template>
