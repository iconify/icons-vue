<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lty3y1n9z.css';
import '../../css/e/ei-47ebjt.css';
import '../../css/g/gcr3q4b8s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lty3y1n9z"/><path class="ei-47ebjt"/><path class="gcr3q4b8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:key" /></template>
