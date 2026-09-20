<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v2ar__b5k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="v2ar__b5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:lattice-tower-with-ball-tip-antenna-on-ground-with-beams" /></template>
