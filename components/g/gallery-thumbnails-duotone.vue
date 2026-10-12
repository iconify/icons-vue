<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/q/q5t4tsbnm.css';
import '../../css/s/sftrilwvg.css';
import '../../css/f/fj5lt5vqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="q5t4tsbnm"/><path class="sftrilwvg"/><path class="fj5lt5vqk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:gallery-thumbnails-duotone" /></template>
