<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dypydkbbu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dypydkbbu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:cloud-snow-solid" /></template>
