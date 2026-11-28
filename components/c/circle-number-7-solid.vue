<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ks-jpshjo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ks-jpshjo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:circle-number-7-solid" /></template>
