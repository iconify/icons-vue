<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zbv__ub4l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zbv__ub4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:dribbble-logo-solid" /></template>
