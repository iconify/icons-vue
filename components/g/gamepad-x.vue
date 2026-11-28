<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dmqluabva.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dmqluabva"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:gamepad-x" /></template>
