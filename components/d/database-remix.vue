<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fwsie36oy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fwsie36oy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:database-remix" /></template>
