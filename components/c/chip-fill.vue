<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jzt_2ac2s.css';
import '../../css/v/vyl_3wa6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jzt_2ac2s"/><path class="vyl_3wa6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:chip-fill" /></template>
