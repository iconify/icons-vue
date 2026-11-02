<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sa3whccfx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sa3whccfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:diameter-fill" /></template>
