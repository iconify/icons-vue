<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wt968xbdq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="wt968xbdq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:codex" /></template>
