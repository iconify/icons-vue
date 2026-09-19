<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wz20asb0x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wz20asb0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:group-alt-filled" /></template>
