<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nvzivcb1m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nvzivcb1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:agent-round" /></template>
