<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/imv4-q93r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="imv4-q93r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:chevrons-up" /></template>
