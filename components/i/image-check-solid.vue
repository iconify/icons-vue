<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wkdo0pbra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wkdo0pbra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:image-check-solid" /></template>
