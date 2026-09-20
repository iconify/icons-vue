<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iqg76lbju.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iqg76lbju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:bookmark-off" /></template>
