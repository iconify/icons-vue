<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/svkb8dgje.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="svkb8dgje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:arrows-down-to-line" /></template>
