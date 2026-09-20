<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ehjlygeom.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ehjlygeom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:e3" /></template>
