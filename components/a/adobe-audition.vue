<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tv-k2s26h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tv-k2s26h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:adobe-audition" /></template>
