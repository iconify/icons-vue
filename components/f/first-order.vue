<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/an3sm_xkv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="an3sm_xkv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:first-order" /></template>
