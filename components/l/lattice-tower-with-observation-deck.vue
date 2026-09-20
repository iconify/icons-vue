<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n0g3nabyd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="n0g3nabyd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:lattice-tower-with-observation-deck" /></template>
