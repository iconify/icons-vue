<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/msphedb2j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="msphedb2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:cube-check" /></template>
