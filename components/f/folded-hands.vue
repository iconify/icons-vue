<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fkwm-bc_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fkwm-bc_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:folded-hands" /></template>
