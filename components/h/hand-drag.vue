<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s516_l97p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s516_l97p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:hand-drag" /></template>
