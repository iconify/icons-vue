<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u8dght63r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":15};
const content = `<path class="u8dght63r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="formkit:compress" /></template>
