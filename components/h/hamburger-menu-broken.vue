<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/c/c_wyezbbg.css';
import '../../css/i/ihwi1gbya.css';
import '../../css/z/zj3_xl2hb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="c_wyezbbg"/><path class="ihwi1gbya"/><path class="zj3_xl2hb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:hamburger-menu-broken" /></template>
