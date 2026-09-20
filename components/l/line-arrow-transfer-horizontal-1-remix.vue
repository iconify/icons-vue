<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bcc5x3bzy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bcc5x3bzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:line-arrow-transfer-horizontal-1-remix" /></template>
