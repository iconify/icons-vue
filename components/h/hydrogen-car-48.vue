<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hkk820mfz.css';
import '../../css/w/w2_kf1b2m.css';
import '../../css/g/g2i6a7muy.css';
import '../../css/b/bi74gbbsh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hkk820mfz"/><path class="w2_kf1b2m"/><path class="g2i6a7muy"/><path class="bi74gbbsh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hydrogen-car-48" /></template>
