<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xvfcm29ft.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xvfcm29ft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:decagram-outline" /></template>
