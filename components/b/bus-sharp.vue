<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pn6mpqodh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pn6mpqodh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:bus-sharp" /></template>
