<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dvg-drbfm.css';
import '../../css/v/vx3fhbbqc.css';
import '../../css/k/kjepdxb8e.css';
import '../../css/j/jthdzbbfe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="dvg-drbfm"/><path class="vx3fhbbqc"/><path class="kjepdxb8e"/><path class="jthdzbbfe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:api-key-20-bold" /></template>
