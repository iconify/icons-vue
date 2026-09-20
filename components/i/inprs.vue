<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j898_bc1h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":120,"height":32.26};
const content = `<path class="j898_bc1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:inprs" /></template>
