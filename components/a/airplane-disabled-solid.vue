<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rfcl9ekst.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rfcl9ekst"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:airplane-disabled-solid" /></template>
