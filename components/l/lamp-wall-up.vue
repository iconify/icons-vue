<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lyhl_60xi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lyhl_60xi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:lamp-wall-up" /></template>
