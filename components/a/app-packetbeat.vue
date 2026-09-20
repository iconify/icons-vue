<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yspu1txce.css';
import '../../css/e/em8icc8zx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ouiIcon__fillSecondary yspu1txce"/><path class="em8icc8zx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:app-packetbeat" /></template>
