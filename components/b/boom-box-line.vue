<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y20ik4bhm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y20ik4bhm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:boom-box-line" /></template>
