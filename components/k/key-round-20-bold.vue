<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pgp4x1bjw.css';
import '../../css/p/p16c5ccou.css';
import '../../css/x/x6y5_jb4k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="pgp4x1bjw"/><path class="p16c5ccou"/><path class="x6y5_jb4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:key-round-20-bold" /></template>
