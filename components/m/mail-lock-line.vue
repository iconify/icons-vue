<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qbce_z4al.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qbce_z4al"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:mail-lock-line" /></template>
