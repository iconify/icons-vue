<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ucgsi_b-h.css';
import '../../css/l/l35tfkbsr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ucgsi_b-h"/><path class="l35tfkbsr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:lightbulb-minimalistic-bold" /></template>
