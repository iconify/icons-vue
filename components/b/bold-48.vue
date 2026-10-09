<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dkl3kalhn.css';
import '../../css/x/xkgq43b2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dkl3kalhn"/><path class="xkgq43b2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bold-48" /></template>
