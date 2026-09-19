<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xntikhq4t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xntikhq4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:ai-crop" /></template>
