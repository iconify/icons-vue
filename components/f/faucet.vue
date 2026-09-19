<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ne263d1fr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ne263d1fr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:faucet" /></template>
