<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mji4-fs_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mji4-fs_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:card-refund-line" /></template>
