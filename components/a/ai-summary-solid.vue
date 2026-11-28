<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/il1opkonq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="il1opkonq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:ai-summary-solid" /></template>
