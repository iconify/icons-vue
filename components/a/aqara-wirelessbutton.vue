<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p_cq7wdxs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p_cq7wdxs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:aqara-wirelessbutton" /></template>
