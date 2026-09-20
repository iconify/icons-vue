<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p4aprabcq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="p4aprabcq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:calendar-mark-solid" /></template>
