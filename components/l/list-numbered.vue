<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/re6ijgajr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="re6ijgajr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:list-numbered" /></template>
