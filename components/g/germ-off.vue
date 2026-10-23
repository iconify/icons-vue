<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vp9f0x88f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vp9f0x88f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:germ-off" /></template>
