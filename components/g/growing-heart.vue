<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/j/jyp5ubbco.css';
import '../../css/v/vz71d8bte.css';
import '../../css/l/lziqluudw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="jyp5ubbco"/><path class="vz71d8bte"/><path class="lziqluudw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:growing-heart" /></template>
