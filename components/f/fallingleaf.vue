<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w2pr8hokp.css';
import '../../css/j/jswp7mbzj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w2pr8hokp"/><path class="jswp7mbzj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:fallingleaf" /></template>
