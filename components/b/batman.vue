<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vc3trkb8n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vc3trkb8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:batman" /></template>
