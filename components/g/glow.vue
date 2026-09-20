<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jdti4s_xp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jdti4s_xp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:glow" /></template>
