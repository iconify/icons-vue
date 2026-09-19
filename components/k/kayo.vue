<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rwe_a9b_b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rwe_a9b_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:kayo" /></template>
