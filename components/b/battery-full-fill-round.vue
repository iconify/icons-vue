<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tpvss8lpt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tpvss8lpt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:battery-full-fill-round" /></template>
