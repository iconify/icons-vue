<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oe_takgho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oe_takgho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cog-counterclockwise" /></template>
