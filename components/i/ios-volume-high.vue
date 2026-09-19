<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tej_g1b-d.css';
import '../../css/n/nwq7urbqo.css';
import '../../css/t/twswkdbiy.css';
import '../../css/p/p7wko903m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tej_g1b-d"/><path class="nwq7urbqo"/><path class="twswkdbiy"/><path class="p7wko903m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-volume-high" /></template>
