<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/igrurgb_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="igrurgb_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:earth-2-remix" /></template>
