<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g88jb2prf.css';
import '../../css/s/s7tj_nz1w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g88jb2prf"/><path class="s7tj_nz1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:car-line" /></template>
