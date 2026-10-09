<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fizh9bcok.css';
import '../../css/b/bi4bqnltf.css';
import '../../css/g/ga2g5dbmp.css';
import '../../css/g/gnp00z80k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fizh9bcok"/><path class="bi4bqnltf"/><path class="ga2g5dbmp"/><path class="gnp00z80k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:energy-flow-20" /></template>
