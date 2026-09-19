<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qqmepabmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qqmepabmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:cloud-bold" /></template>
