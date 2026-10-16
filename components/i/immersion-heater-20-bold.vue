<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i5zgux56h.css';
import '../../css/e/egsafqdij.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="i5zgux56h"/><path class="egsafqdij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:immersion-heater-20-bold" /></template>
