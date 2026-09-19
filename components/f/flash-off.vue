<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/ve-_k2a0b.css';
import '../../css/o/o0xw4kbra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ve-_k2a0b"/><path class="o0xw4kbra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:flash-off" /></template>
