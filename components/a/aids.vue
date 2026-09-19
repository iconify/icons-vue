<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n7j3vib8h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":24};
const content = `<path class="n7j3vib8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:aids" /></template>
