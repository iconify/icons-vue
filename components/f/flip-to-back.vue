<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dvdiahk1x.css';
import '../../css/y/yphrhqbrt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dvdiahk1x"/><path class="yphrhqbrt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:flip-to-back" /></template>
