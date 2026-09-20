<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mmqp0_b3c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mmqp0_b3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:amazon-prime-video-logo-1-block" /></template>
