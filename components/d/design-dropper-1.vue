<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ru1pniv2i.css';
import '../../css/l/lluucabrf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ru1pniv2i"/><path class="lluucabrf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:design-dropper-1" /></template>
