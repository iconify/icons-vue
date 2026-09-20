<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/urkx-c35c.css';
import '../../css/k/kwzja8bzb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="urkx-c35c"/><path class="kwzja8bzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-pipe-open" /></template>
