<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-trz4bsf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p-trz4bsf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:cloud-wifi-solid" /></template>
