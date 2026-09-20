<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d7v_mpb_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="d7v_mpb_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:auto-flash-remix" /></template>
