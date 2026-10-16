<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gm_-_fgwp.css';
import '../../css/k/kicqyzbtl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gm_-_fgwp"/><path class="kicqyzbtl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:control-rod-48" /></template>
