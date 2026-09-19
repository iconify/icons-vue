<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/t/to1cgjbzi.css';
import '../../css/p/phhpl4biy.css';
import '../../css/y/y60xx1bkg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="to1cgjbzi"/><path class="phhpl4biy"/><path class="y60xx1bkg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:chemistry-02" /></template>
