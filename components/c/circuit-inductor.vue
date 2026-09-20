<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/ws59vcmvr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ws59vcmvr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:circuit-inductor" /></template>
