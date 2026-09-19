<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g4-rnsbij.css';
import '../../css/m/mf2yaebts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g4-rnsbij"/><path class="mf2yaebts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:baseball-sharp" /></template>
