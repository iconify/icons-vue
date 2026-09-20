<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lor3pcgfs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lor3pcgfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:hemisphere-2-line" /></template>
