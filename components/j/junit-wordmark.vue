<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vl9r37boe.css';
import '../../css/f/fmyd_bcdu.css';
import '../../css/g/gody8syjs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="vl9r37boe"/><path class="fmyd_bcdu"/><path class="gody8syjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:junit-wordmark" /></template>
