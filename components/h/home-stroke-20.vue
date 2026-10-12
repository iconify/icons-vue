<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p9kr3ubxk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="p9kr3ubxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:home-stroke-20" /></template>
