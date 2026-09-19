<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ov0tgp1pd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ov0tgp1pd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:heavy-dollar-sign" /></template>
