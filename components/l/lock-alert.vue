<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xr-godbah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xr-godbah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:lock-alert" /></template>
