<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iuqr6acyi.css';
import '../../css/b/bp937cc8x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="iuqr6acyi"/><path class="bp937cc8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:battery-fire-48" /></template>
