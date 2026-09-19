<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/s/sz0ei6zup.css';
import '../../css/z/z9jpn_beu.css';
import '../../css/y/y8m0unbnp.css';
import '../../css/n/nz3crbbcj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="sz0ei6zup"/><path class="z9jpn_beu"/><path class="y8m0unbnp"/><path class="nz3crbbcj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:cable-car" /></template>
