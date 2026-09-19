<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/smiam64jy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="smiam64jy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:camera-stroke-12" /></template>
