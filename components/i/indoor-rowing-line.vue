<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ov26wzbtk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ov26wzbtk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:indoor-rowing-line" /></template>
