<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/es8mo68gx.css';
import '../../css/c/cdj2jkbik.css';
import '../../css/p/p91j9gb3y.css';
import '../../css/b/bl5dnqrrh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="es8mo68gx"/><path class="cdj2jkbik"/><path class="p91j9gb3y"/><path class="bl5dnqrrh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:inboxtray" /></template>
