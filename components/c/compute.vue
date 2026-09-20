<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nwotdib6l.css';
import '../../css/b/bhhw35bml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="nwotdib6l"/><rect class="bhhw35bml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:compute" /></template>
