<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lmbc0tbrq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="lmbc0tbrq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:calendar-check-solid" /></template>
