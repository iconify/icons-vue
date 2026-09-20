<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b819-vbmh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b819-vbmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:car-speed-limiter" /></template>
