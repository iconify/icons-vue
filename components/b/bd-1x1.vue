<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nxa_324eo.css';
import '../../css/s/s79t828hd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nxa_324eo"/><circle class="s79t828hd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flag:bd-1x1" /></template>
