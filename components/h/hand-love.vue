<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hv0_sebma.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hv0_sebma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:hand-love" /></template>
