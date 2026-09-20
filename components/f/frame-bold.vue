<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ygrpgv_sq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ygrpgv_sq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:frame-bold" /></template>
