<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xrvvg0bhz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xrvvg0bhz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:centralized" /></template>
