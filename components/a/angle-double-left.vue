<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m0b4cdb4f.css';
import '../../css/t/towwv1e5k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="m0b4cdb4f"/><path class="towwv1e5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:angle-double-left" /></template>
