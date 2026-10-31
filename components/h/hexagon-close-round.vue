<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dv6pukbdz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dv6pukbdz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:hexagon-close-round" /></template>
