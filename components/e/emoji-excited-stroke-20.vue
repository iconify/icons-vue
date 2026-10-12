<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u5dk3pbjk.css';
import '../../css/j/jpdmwmb0j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="u5dk3pbjk"/><path class="jpdmwmb0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:emoji-excited-stroke-20" /></template>
