<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rmqdh1b0n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rmqdh1b0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:inkscape" /></template>
