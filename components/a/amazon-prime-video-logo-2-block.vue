<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ro_yicc4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ro_yicc4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:amazon-prime-video-logo-2-block" /></template>
