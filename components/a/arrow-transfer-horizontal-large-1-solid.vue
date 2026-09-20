<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tqee7sb9p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tqee7sb9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:arrow-transfer-horizontal-large-1-solid" /></template>
