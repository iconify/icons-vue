<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gs6656bhq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gs6656bhq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:ceiling-lamp" /></template>
