<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z_5z_09wh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z_5z_09wh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mi:cloud-upload" /></template>
