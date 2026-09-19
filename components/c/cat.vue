<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m5xcf3m3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m5xcf3m3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:cat" /></template>
