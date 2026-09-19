<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m5pi2sbje.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m5pi2sbje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:border-full" /></template>
