<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/r/rkzreok7b.css';
import '../../css/q/qlseadceb.css';
import '../../css/c/c25lkgbgb.css';
import '../../css/c/ca5b8gbur.css';
import '../../css/r/rwnv8qbti.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="rkzreok7b"/><path class="qlseadceb"/><path class="c25lkgbgb"/><path class="ca5b8gbur"/><path class="rwnv8qbti"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:case-minimalistic-broken" /></template>
