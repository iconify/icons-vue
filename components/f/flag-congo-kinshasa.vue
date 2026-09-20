<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cnqa97brp.css';
import '../../css/f/fhxr92bhq.css';
import '../../css/r/rt5epac7j.css';
import '../../css/q/qy525jbwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="cnqa97brp"/><path class="fhxr92bhq"/><path class="rt5epac7j"/><path class="qy525jbwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:flag-congo-kinshasa" /></template>
