<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pxo4dlcet.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pxo4dlcet"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:arrow-down-sharp" /></template>
