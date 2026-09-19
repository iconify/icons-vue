<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mi18t8sbh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="mi18t8sbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:calculator" /></template>
