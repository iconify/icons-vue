<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mfd1srn4h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mfd1srn4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:drone-off" /></template>
