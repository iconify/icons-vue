<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qsd1wlbdz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qsd1wlbdz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:logout" /></template>
