<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ld6k-wbdq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ld6k-wbdq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:home-sound-out" /></template>
