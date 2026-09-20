<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rsk20ca5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rsk20ca5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:gender-lesbian-2-remix" /></template>
