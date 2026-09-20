<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/smpgmkb8n.css';
import '../../css/i/iush4bsal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="smpgmkb8n"/><path class="iush4bsal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:end-arrow" /></template>
