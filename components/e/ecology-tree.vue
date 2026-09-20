<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g_5i6l4fk.css';
import '../../css/l/lrz954bus.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="g_5i6l4fk"/><path class="lrz954bus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:ecology-tree" /></template>
