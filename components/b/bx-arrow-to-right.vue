<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t8u8ch62e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t8u8ch62e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-arrow-to-right" /></template>
