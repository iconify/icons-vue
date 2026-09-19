<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hfxe2qbrn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hfxe2qbrn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:btc" /></template>
