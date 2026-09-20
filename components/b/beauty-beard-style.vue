<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qhl1isbvq.css';
import '../../css/s/sdbok-sel.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qhl1isbvq"/><path class="sdbok-sel"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:beauty-beard-style" /></template>
