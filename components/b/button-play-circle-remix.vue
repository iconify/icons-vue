<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sjwt4m9cs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="sjwt4m9cs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:button-play-circle-remix" /></template>
