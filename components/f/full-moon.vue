<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ciqskgrxn.css';
import '../../css/c/c5a_m3jtk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<circle class="ciqskgrxn"/><circle class="c5a_m3jtk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:full-moon" /></template>
