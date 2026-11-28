<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uhha2ndkb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uhha2ndkb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:contract-edit" /></template>
