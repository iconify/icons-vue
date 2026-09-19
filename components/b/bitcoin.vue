<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yc0sti72g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yc0sti72g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:bitcoin" /></template>
