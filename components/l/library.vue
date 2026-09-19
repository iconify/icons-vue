<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fl933tb7k.css';
import '../../css/s/s-5hvuboc.css';
import '../../css/k/k68b7sadh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fl933tb7k"/><path class="s-5hvuboc"/><path class="k68b7sadh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:library" /></template>
