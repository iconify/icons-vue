<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xrgc3zb_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="xrgc3zb_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:magic-wand-1-remix" /></template>
