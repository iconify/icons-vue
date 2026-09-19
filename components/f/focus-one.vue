<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/u/ufpp1dblg.css';
import '../../css/o/orq9p0bfg.css';
import '../../css/w/wp7vq6b7w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="ufpp1dblg"/><path class="orq9p0bfg"/><path class="wp7vq6b7w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:focus-one" /></template>
