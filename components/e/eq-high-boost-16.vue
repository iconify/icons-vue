<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qh9jl8b2r.css';
import '../../css/g/gis6lfbgu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qh9jl8b2r"/><path class="gis6lfbgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:eq-high-boost-16" /></template>
