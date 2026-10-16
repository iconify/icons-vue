<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z6og01bov.css';
import '../../css/i/ijpeexi0x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="z6og01bov"/><path class="ijpeexi0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:carbon-price-20" /></template>
