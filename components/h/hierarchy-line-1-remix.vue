<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tpu_c0btc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tpu_c0btc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:hierarchy-line-1-remix" /></template>
