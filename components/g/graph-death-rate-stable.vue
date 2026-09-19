<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/g/gsx59ilbo.css';
import '../../css/r/ro9sclw5a.css';
import '../../css/g/gmeghdcvi.css';
import '../../css/e/es8z9e5se.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="gsx59ilbo"/><path class="ro9sclw5a"/><path class="gmeghdcvi"/><path class="es8z9e5se"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="covid:graph-death-rate-stable" /></template>
