<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f4_lr111l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f4_lr111l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:earth" /></template>
