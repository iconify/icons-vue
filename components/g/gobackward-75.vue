<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u9wi5p_9x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="u9wi5p_9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:gobackward-75" /></template>
