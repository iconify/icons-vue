<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c5xw7my_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":408};
const content = `<path class="c5xw7my_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:airline-seat-recline-extra" /></template>
