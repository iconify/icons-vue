<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/l-1rtqbij.css';
import '../../css/w/wkithdmnp.css';
import '../../css/m/myal57b7v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="l-1rtqbij"/><path class="wkithdmnp"/><path class="myal57b7v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:gear" /></template>
