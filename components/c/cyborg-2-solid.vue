<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fgbyfmp5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="fgbyfmp5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:cyborg-2-solid" /></template>
