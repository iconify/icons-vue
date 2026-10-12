<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qj2x0ebtf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qj2x0ebtf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:funnel-filled" /></template>
