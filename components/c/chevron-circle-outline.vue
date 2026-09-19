<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/mgang7m8j.css';
import '../../css/a/ayf976bbf.css';
import '../../css/k/k2hrn-b1v.css';
import '../../css/h/hpjm41bbr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="mgang7m8j"/><path clip-rule="evenodd" class="ayf976bbf"/><path class="k2hrn-b1v"/><path clip-rule="evenodd" class="hpjm41bbr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:chevron-circle-outline" /></template>
