<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-v70nb4h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f-v70nb4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:chart" /></template>
