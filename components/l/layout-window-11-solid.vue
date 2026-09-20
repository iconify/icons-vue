<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kbyi2ub1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="kbyi2ub1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:layout-window-11-solid" /></template>
