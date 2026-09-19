<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/hltyj8b6l.css';
import '../../css/c/ctk3_x4ut.css';
import '../../css/i/iq3e-sygp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="hltyj8b6l"/><path class="ctk3_x4ut"/><path class="iq3e-sygp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:industry-duo" /></template>
