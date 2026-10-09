<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rnjkukbmw.css';
import '../../css/o/ozisc9lak.css';
import '../../css/w/waeycxb3h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rnjkukbmw"/><path class="ozisc9lak"/><path class="waeycxb3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:carbon-offset-20" /></template>
