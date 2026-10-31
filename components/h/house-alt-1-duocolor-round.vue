<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qfxdh1bjz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qfxdh1bjz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-alt-1-duocolor-round" /></template>
