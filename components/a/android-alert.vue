<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m5fxqqbvg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m5fxqqbvg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:android-alert" /></template>
