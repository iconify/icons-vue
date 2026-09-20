<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vw7q4hb_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="vw7q4hb_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:curling" /></template>
