<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qx3mfibsg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qx3mfibsg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:layers-edit" /></template>
