<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xfcpigbog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xfcpigbog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:audacity-logo-block" /></template>
