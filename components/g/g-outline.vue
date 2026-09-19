<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pdeiz2vni.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="pdeiz2vni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:g-outline" /></template>
