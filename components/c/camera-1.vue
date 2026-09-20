<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/kezo00-ru.css';
import '../../css/h/hringyqtb.css';
import '../../css/s/sbry_navz.css';
import '../../css/i/i34px_bie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="kezo00-ru"/><path class="hringyqtb"/><path class="sbry_navz"/><path class="i34px_bie"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:camera-1" /></template>
