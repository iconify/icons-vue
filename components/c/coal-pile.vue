<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bimtsqb7o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bimtsqb7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:coal-pile" /></template>
