<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qr3ad0btl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qr3ad0btl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:cuboid-fill" /></template>
