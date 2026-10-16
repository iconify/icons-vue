<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x5i9cpbbm.css';
import '../../css/c/cc-1-6bif.css';
import '../../css/n/nbl98olvj.css';
import '../../css/j/j5zi96b7l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="x5i9cpbbm"/><path class="cc-1-6bif"/><path class="nbl98olvj"/><path class="j5zi96b7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:extractor-fan-48" /></template>
