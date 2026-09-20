<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/svh0msb2e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="svh0msb2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:dual-screen-filled" /></template>
