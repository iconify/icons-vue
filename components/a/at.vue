<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mcu4mj0fs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mcu4mj0fs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:at" /></template>
