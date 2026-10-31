<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xgtx0hbdn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xgtx0hbdn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cursor-bulk-round" /></template>
