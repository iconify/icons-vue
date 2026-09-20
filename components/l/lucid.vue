<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/seiyok0se.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="seiyok0se"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:lucid" /></template>
