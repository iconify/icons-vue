<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/abx036wst.css';
import '../../css/n/nv2jz3bhl.css';
import '../../css/l/l3pzy9htd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="abx036wst"/><path class="nv2jz3bhl"/><path class="l3pzy9htd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-car" /></template>
