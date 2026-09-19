<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/i/irwinbc_r.css';
import '../../css/w/wimlky-am.css';
import '../../css/c/ch1wpxbeu.css';
import '../../css/l/l5xzt3e9a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="irwinbc_r"/><path class="wimlky-am"/><path class="ch1wpxbeu"/><path class="l5xzt3e9a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:car-bump-outline" /></template>
