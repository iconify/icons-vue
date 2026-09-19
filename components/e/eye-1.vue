<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9tr6bcfx.css';
import '../../css/n/n2wcz0b2s.css';
import '../../css/b/bjh1f82tm.css';
import '../../css/h/hx6xedbpi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="y9tr6bcfx"><path class="n2wcz0b2s"/><path class="bjh1f82tm"/><path class="hx6xedbpi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:eye-1" /></template>
