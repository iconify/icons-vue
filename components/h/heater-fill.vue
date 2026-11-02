<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e4zwch5ns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e4zwch5ns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:heater-fill" /></template>
