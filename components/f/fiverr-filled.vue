<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/akoau_biy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="akoau_biy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:fiverr-filled" /></template>
