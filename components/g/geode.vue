<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cme8g-blb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cme8g-blb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:geode" /></template>
