<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pe4o03z-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pe4o03z-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:costco" /></template>
