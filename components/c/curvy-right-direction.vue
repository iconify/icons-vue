<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kkq6cdz7p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kkq6cdz7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:curvy-right-direction" /></template>
