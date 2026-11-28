<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nyfpfsbxr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nyfpfsbxr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:heading-3-solid" /></template>
