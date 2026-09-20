<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ahv5oyb-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ahv5oyb-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:candle-solid" /></template>
