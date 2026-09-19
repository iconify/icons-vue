<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/irpgc2biy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":750,"height":750};
const content = `<path class="irpgc2biy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="il:image" /></template>
