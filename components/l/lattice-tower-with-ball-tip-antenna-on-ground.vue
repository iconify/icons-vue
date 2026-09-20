<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kqhiw328v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="kqhiw328v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:lattice-tower-with-ball-tip-antenna-on-ground" /></template>
