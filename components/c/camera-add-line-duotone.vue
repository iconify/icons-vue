<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/b/bvdn8gb_z.css';
import '../../css/z/zek-ufbop.css';
import '../../css/m/mw2j0bfon.css';
import '../../css/u/u4qnnrb5s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="bvdn8gb_z"/><path class="zek-ufbop"/><path class="mw2j0bfon"/><path class="u4qnnrb5s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:camera-add-line-duotone" /></template>
