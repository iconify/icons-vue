<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ot-zu_b2p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ot-zu_b2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:changing-room-hanger" /></template>
