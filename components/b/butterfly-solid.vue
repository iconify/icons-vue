<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/re1y-rbgv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="re1y-rbgv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:butterfly-solid" /></template>
