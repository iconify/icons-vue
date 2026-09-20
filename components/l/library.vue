<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vpp1e8baq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vpp1e8baq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:library" /></template>
