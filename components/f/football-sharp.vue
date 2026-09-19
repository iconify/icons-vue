<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zgiziy1ns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zgiziy1ns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:football-sharp" /></template>
