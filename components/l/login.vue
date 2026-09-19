<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mzx31b0pu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mzx31b0pu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:login" /></template>
