<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cypfrkb_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="cypfrkb_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:align-center" /></template>
