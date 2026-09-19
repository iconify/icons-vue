<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hal55f1hv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hal55f1hv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:fluffy-trefoil" /></template>
