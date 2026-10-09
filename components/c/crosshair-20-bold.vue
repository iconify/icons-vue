<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nain0n-0j.css';
import '../../css/z/zr6oosbmg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="nain0n-0j"/><path class="zr6oosbmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:crosshair-20-bold" /></template>
