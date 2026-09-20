<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xbw7r3bce.css';
import '../../css/t/tcu8_9yus.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xbw7r3bce"/><path clip-rule="evenodd" class="tcu8_9yus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:jinritoutiao" /></template>
