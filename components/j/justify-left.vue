<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ri_vl6b7t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ri_vl6b7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:justify-left" /></template>
