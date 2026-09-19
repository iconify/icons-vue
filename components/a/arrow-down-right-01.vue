<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qr0_a1bsl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qr0_a1bsl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:arrow-down-right-01" /></template>
