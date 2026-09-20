<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rot5gv2bf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rot5gv2bf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:browser-error-remix" /></template>
