<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vtk5ue39c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vtk5ue39c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:generic-device-io-unavailable" /></template>
