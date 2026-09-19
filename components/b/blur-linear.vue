<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/clg13_kjw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="clg13_kjw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:blur-linear" /></template>
