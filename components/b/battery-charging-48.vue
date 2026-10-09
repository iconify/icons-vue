<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l73ftcc0i.css';
import '../../css/v/vimw34l9o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="l73ftcc0i"/><path class="vimw34l9o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:battery-charging-48" /></template>
