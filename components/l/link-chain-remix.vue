<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aswp9gckx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aswp9gckx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:link-chain-remix" /></template>
