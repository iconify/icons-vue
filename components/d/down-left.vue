<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xizzrhbul.css';
import '../../css/h/h5p4sr09b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xizzrhbul"/><path class="h5p4sr09b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:down-left" /></template>
