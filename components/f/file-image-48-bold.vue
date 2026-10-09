<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pdos38jip.css';
import '../../css/k/kcfd8k4na.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pdos38jip"/><path class="kcfd8k4na"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:file-image-48-bold" /></template>
