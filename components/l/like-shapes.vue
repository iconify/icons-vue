<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/k/kaw7birim.css';
import '../../css/v/vk3y0vbad.css';
import '../../css/f/fc1qebbtl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="kaw7birim"/><path class="vk3y0vbad"/><path class="fc1qebbtl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:like-shapes" /></template>
