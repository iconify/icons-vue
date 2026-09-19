<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fx1192bjs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1248,"height":1664};
const content = `<path class="fx1192bjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:bitcoin" /></template>
