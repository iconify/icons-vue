<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/n77u17bxl.css';
import '../../css/k/k885mybol.css';
import '../../css/n/n9z_vqbki.css';
import '../../css/a/a-li4fbcy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="n77u17bxl"/><path class="k885mybol"/><path clip-rule="evenodd" class="n9z_vqbki"/><path class="a-li4fbcy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:battery-bolt-duo" /></template>
