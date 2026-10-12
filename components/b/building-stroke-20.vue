<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/grhpkv0pg.css';
import '../../css/f/fc-vduj0h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="grhpkv0pg"/><path class="fc-vduj0h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:building-stroke-20" /></template>
