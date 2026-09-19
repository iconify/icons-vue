<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yz-k7ho-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yz-k7ho-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:hexagon-01" /></template>
