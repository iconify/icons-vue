<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mu4kwc0bq.css';
import '../../css/s/sma_z600n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mu4kwc0bq"/><path clip-rule="evenodd" class="sma_z600n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:brick-wall-fire-filled" /></template>
