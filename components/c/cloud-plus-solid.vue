<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ph4xfwbpj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ph4xfwbpj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:cloud-plus-solid" /></template>
