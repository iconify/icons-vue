<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/mph5d6z2j.css';
import '../../css/b/bas90cbxo.css';
import '../../css/w/w80_64pdj.css';
import '../../css/w/wy8mnub5w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="mph5d6z2j wm-k"/><path class="bas90cbxo wm-k"/><path class="w80_64pdj wm-k"/><path class="wm-shine wy8mnub5w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-anime:circle" /></template>
