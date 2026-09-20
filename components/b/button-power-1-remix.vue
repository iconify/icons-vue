<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vr5s-2baf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="vr5s-2baf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:button-power-1-remix" /></template>
