<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x9c0rinbm.css';
import '../../css/c/cj564hbjs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x9c0rinbm"/><path clip-rule="evenodd" class="cj564hbjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:hospital-2" /></template>
