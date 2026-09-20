<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i3djctx0v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i3djctx0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:intersex-symbol" /></template>
