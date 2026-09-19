<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ohrioug2t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="ohrioug2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:alt-text-stroke-12" /></template>
