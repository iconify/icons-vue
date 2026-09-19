<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xy-4x9bfo.css';
import '../../css/p/pb7t6bclw.css';
import '../../css/t/tvu3xz-hl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="xy-4x9bfo"/><path class="pb7t6bclw"/><path class="tvu3xz-hl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:contract-line" /></template>
