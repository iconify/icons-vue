<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vdpazwbdo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vdpazwbdo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:keystone" /></template>
