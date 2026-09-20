<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yr0d0kx5t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yr0d0kx5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:cake-solid" /></template>
