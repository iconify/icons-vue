<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ranh4pb3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="ranh4pb3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:angular" /></template>
