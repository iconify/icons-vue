<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sd-3_xxsi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sd-3_xxsi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:bluetooth-searching-solid" /></template>
