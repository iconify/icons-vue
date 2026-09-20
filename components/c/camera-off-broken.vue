<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/b/blo41m3ob.css';
import '../../css/u/u4qnnrb5s.css';
import '../../css/a/aizjr31qw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="blo41m3ob"/><path class="u4qnnrb5s"/><path class="aizjr31qw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:camera-off-broken" /></template>
