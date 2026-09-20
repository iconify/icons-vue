<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l_de38b0p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="l_de38b0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:arrow-left-from-rectangle-tall-outline" /></template>
