<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ib3rsc9pe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ib3rsc9pe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:android-watch" /></template>
