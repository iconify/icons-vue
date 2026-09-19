<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nf7ks3r1j.css';
import '../../css/x/xnk1gt9lb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="nf7ks3r1j"/><path class="xnk1gt9lb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:file-pdf" /></template>
