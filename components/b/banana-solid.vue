<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vtv1suskr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vtv1suskr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:banana-solid" /></template>
