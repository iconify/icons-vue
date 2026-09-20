<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/f1xuy0btj.css';
import '../../css/s/sixfdvbze.css';
import '../../css/i/iucnxxyud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="f1xuy0btj"/><path class="sixfdvbze"/><path class="iucnxxyud"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:gallery-favourite-broken" /></template>
