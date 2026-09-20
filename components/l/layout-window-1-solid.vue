<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p50x5tbmw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="p50x5tbmw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:layout-window-1-solid" /></template>
