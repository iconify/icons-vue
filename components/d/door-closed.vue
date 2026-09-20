<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rszqa-p5t.css';
import '../../css/n/n8-3fdb7j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rszqa-p5t"/><path class="n8-3fdb7j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:door-closed" /></template>
