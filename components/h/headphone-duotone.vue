<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/kn98ytb9h.css';
import '../../css/q/qudzvcbhp.css';
import '../../css/k/kfczycb2v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="kn98ytb9h"/><path class="qudzvcbhp"/><path class="kfczycb2v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:headphone-duotone" /></template>
