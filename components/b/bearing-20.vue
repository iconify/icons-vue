<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r4bjo-bjt.css';
import '../../css/t/tiuaiabal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="r4bjo-bjt"/><path class="tiuaiabal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bearing-20" /></template>
