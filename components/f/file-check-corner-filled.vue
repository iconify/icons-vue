<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uvncfgbpp.css';
import '../../css/r/roohfabdx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uvncfgbpp"/><path class="roohfabdx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:file-check-corner-filled" /></template>
