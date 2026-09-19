<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ecm9edcrh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":392};
const content = `<path class="ecm9edcrh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:favorite-outline" /></template>
