<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jhjotkbwy.css';
import '../../css/c/cm6wfkb8h.css';
import '../../css/e/e3wqdcuin.css';
import '../../css/p/pvfareb-d.css';
import '../../css/i/imf9zcbhu.css';
import '../../css/u/ujot87bwi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jhjotkbwy"/><path class="cm6wfkb8h"/><path class="e3wqdcuin"/><path class="pvfareb-d"/><path clip-rule="evenodd" class="imf9zcbhu"/><path clip-rule="evenodd" class="ujot87bwi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:eye-scan-outline" /></template>
