<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/of8ozpb-y.css';
import '../../css/n/nk1dwkb8d.css';
import '../../css/t/tm6yvh82x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="of8ozpb-y"/><path class="nk1dwkb8d"/><path class="tm6yvh82x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:helideck-48-bold" /></template>
