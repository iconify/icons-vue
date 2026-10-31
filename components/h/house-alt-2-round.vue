<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sjpct4_2a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sjpct4_2a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-alt-2-round" /></template>
