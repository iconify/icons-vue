<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x-fh5kbgy.css';
import '../../css/n/nw5k1bbvg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="x-fh5kbgy"/><path class="nw5k1bbvg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:clipboard-list-stroke-12" /></template>
