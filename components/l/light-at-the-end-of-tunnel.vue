<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u0p-a1baf.css';
import '../../css/u/uu8vm-ber.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="u0p-a1baf"/><path class="uu8vm-ber"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:light-at-the-end-of-tunnel" /></template>
