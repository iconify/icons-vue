<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t1y1e7-dj.css';
import '../../css/d/dz2ndeb-q.css';
import '../../css/o/o7tbp8bzr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<defs><linearGradient id="SVGQnyPAd2z" x1="0" x2="128" y1="64" y2="64" gradientUnits="userSpaceOnUse"><stop offset="0" class="t1y1e7-dj"/><stop offset="1" class="dz2ndeb-q"/></linearGradient></defs><path fill="url(#SVGQnyPAd2z)" class="o7tbp8bzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:inertiajs" /></template>
