<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iccsyvk3j.css';
import '../../css/i/ipywdhbyk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="iccsyvk3j"/><path class="ipywdhbyk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:file-sparkle-20-bold" /></template>
