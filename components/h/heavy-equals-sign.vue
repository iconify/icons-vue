<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/murjelbxg.css';
import '../../css/y/y_31qtbyx.css';
import '../../css/x/xoiqtfx8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="murjelbxg"/><path class="y_31qtbyx"/><path class="xoiqtfx8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:heavy-equals-sign" /></template>
