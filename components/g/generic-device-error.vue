<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u-vuseb1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u-vuseb1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:generic-device-error" /></template>
