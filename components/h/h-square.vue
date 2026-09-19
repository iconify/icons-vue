<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nt_ihrbvp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1792};
const content = `<path class="nt_ihrbvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:h-square" /></template>
