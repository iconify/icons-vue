<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ffaginb4b.css';
import '../../css/i/i1z3osb_g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ffaginb4b"/><path class="i1z3osb_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:battery-100-16" /></template>
