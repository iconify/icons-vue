<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cvek_hfww.css';
import '../../css/i/inswb7bej.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="cvek_hfww"/><path class="inswb7bej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:cpp" /></template>
