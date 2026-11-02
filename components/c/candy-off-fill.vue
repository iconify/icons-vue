<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p08m16bwd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p08m16bwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:candy-off-fill" /></template>
