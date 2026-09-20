<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iq8v6ibzh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="iq8v6ibzh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:laptop-camera-solid" /></template>
