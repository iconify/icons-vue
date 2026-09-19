<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/por8_p__f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="por8_p__f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:bus-alt" /></template>
