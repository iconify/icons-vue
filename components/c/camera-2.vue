<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/a/a9bub1fqj.css';
import '../../css/q/qsokfzbll.css';
import '../../css/f/fbsjc3a0u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><rect class="a9bub1fqj"/><circle class="qsokfzbll"/><path class="fbsjc3a0u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:camera-2" /></template>
