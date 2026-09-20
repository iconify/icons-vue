<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fxozdjbjq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fxozdjbjq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:align-left" /></template>
