<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s1tihnb2l.css';
import '../../css/q/qersjhb_f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="s1tihnb2l"/><path class="qersjhb_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:interface-essential-alert-caution" /></template>
