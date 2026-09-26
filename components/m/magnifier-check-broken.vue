<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/o/o3o_tvbax.css';
import '../../css/x/x09loybdy.css';
import '../../css/f/fzogdacmp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="o3o_tvbax"/><path class="x09loybdy"/><path class="fzogdacmp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:magnifier-check-broken" /></template>
