<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qxc_o1bzn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qxc_o1bzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:corner-notch-solid" /></template>
