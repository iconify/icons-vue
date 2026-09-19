<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipkl84b6w.css';
import '../../css/o/odbzuac1h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ipkl84b6w"/><path class="odbzuac1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:globe" /></template>
