<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qzv7ahb5l.css';
import '../../css/j/jmwk00zjz.css';
import '../../css/a/ajpasxnjv.css';
import '../../css/d/d4i9wcynv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qzv7ahb5l"/><path class="jmwk00zjz"/><path class="ajpasxnjv"/><path class="d4i9wcynv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:g-clamp-20-bold" /></template>
