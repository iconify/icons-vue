<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e3kkv50ki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e3kkv50ki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:expand-horizontal-solid" /></template>
