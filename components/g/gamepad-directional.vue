<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hkb8q8ewt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hkb8q8ewt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:gamepad-directional" /></template>
