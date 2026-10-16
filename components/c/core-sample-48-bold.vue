<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r0tg29byf.css';
import '../../css/u/uy3553_vn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="r0tg29byf"/><path class="uy3553_vn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:core-sample-48-bold" /></template>
