<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oi4vo2skc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oi4vo2skc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-right-from-line-fill-round" /></template>
