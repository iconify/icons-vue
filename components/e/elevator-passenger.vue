<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iq_3l-byg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iq_3l-byg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:elevator-passenger" /></template>
