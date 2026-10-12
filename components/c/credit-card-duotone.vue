<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/s805e4aqh.css';
import '../../css/j/joz_vvjya.css';
import '../../css/f/f0o5p1bcf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="s805e4aqh"/><path class="joz_vvjya"/><path class="f0o5p1bcf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:credit-card-duotone" /></template>
