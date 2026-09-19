<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/ve5lq_olz.css';
import '../../css/q/qmbsycchv.css';
import '../../css/o/o3xhv7enl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ve5lq_olz"/><path class="qmbsycchv"/><path class="o3xhv7enl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:data-sheet" /></template>
