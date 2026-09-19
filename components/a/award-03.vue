<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/id7gw1cir.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="id7gw1cir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:award-03" /></template>
