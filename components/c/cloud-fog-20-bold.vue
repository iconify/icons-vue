<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v_p5btbjw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="v_p5btbjw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cloud-fog-20-bold" /></template>
