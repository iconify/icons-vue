<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9tr6bcfx.css';
import '../../css/p/prztxk67h.css';
import '../../css/s/st0k6jbed.css';
import '../../css/y/y-a0iibgi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="y9tr6bcfx"><path class="prztxk67h"/><path class="st0k6jbed"/><path class="y-a0iibgi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:album-collection" /></template>
