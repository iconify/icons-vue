<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l0xf09b2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l0xf09b2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cube-send" /></template>
