<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t5xx1xbsh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t5xx1xbsh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:add-pdf-solid" /></template>
