<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z8ky2vdcs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z8ky2vdcs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:cloud-check-solid" /></template>
