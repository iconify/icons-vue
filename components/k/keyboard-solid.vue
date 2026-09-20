<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h4xr-1bwp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h4xr-1bwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:keyboard-solid" /></template>
