<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qmzpjbyhe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="qmzpjbyhe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:iris-scan-remix" /></template>
