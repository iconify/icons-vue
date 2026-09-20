<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zrbbr2bgq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="zrbbr2bgq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:color-picker-solid" /></template>
