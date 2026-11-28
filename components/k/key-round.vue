<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/drarmh_dl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="drarmh_dl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:key-round" /></template>
