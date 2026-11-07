<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cx30rnqyk.css';
import '../../css/g/g-qkl-bcv.css';
import '../../css/e/em089opbt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cx30rnqyk"/><path class="g-qkl-bcv"/><path class="em089opbt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bluetooth-wave-bold" /></template>
