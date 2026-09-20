<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i_oaqpieo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="i_oaqpieo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:fullscreen-enter" /></template>
