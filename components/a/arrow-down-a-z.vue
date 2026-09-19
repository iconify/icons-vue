<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pnc9p5h0d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pnc9p5h0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:arrow-down-a-z" /></template>
