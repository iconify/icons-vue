<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p4_2h8_8k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p4_2h8_8k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:chart-area-filled" /></template>
