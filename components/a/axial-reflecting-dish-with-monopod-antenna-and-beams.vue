<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jormnbcqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="jormnbcqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:axial-reflecting-dish-with-monopod-antenna-and-beams" /></template>
