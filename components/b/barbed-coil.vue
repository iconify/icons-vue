<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cxoud4tuw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cxoud4tuw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:barbed-coil" /></template>
