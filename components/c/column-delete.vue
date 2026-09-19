<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/m/mwn8sscbi.css';
import '../../css/u/ufk3re2ji.css';
import '../../css/n/n4jxhabgi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="mwn8sscbi"/><path class="ufk3re2ji"/><path class="n4jxhabgi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:column-delete" /></template>
