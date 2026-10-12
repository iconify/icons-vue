<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pa8498bbc.css';
import '../../css/a/aqsnv9bnd.css';
import '../../css/h/hayl1lfmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="pa8498bbc"/><path class="aqsnv9bnd"/><path class="hayl1lfmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bookmark-minus-20-bold" /></template>
