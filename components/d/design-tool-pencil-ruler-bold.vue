<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mzjr1sbqy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mzjr1sbqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:design-tool-pencil-ruler-bold" /></template>
