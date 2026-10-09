<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r7olx61gw.css';
import '../../css/k/kbqy29bmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="r7olx61gw"/><path class="kbqy29bmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hard-drive-48" /></template>
