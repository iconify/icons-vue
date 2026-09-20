<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kcfzw-bzn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kcfzw-bzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:deepai" /></template>
