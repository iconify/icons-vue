<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vqtnr_bby.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="primary vqtnr_bby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:ladder-duotone" /></template>
