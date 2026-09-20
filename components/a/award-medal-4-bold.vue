<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ycs9x2bve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ycs9x2bve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:award-medal-4-bold" /></template>
