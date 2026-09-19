<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pf0z39bmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pf0z39bmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:house-keys" /></template>
