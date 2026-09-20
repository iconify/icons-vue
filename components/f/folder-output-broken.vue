<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/i/i02wx60ix.css';
import '../../css/d/d0h1ndbsd.css';
import '../../css/r/rx259hx4x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="i02wx60ix"/><path class="d0h1ndbsd"/><path class="rx259hx4x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:folder-output-broken" /></template>
