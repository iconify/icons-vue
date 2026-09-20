<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g_svioi-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="g_svioi-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:dot" /></template>
