<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c1z4cb9qa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c1z4cb9qa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:basketball" /></template>
