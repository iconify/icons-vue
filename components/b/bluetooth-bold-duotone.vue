<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kg5mtsbge.css';
import '../../css/e/eiwc-7x-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kg5mtsbge"/><path class="eiwc-7x-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bluetooth-bold-duotone" /></template>
