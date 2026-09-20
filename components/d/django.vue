<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t-wdiqbjd.css';
import '../../css/i/it2p9rrcl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="t-wdiqbjd"/><path class="it2p9rrcl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:django" /></template>
