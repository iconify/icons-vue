<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o72e3cdbb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o72e3cdbb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:baggage" /></template>
