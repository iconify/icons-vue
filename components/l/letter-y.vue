<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wdg-icb3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wdg-icb3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:letter-y" /></template>
