<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pbt65ccmj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pbt65ccmj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:gas-station-line" /></template>
