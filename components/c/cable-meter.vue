<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lpvwby7ij.css';
import '../../css/t/tq2qnvbug.css';
import '../../css/k/k-njt2b4a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="lpvwby7ij"/><path class="tq2qnvbug"/><path class="k-njt2b4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:cable-meter" /></template>
