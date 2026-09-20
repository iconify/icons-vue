<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xoyp3cbmk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="xoyp3cbmk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:emergency-exit-remix" /></template>
