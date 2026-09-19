<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ps25r6b3w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ps25r6b3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:dome-light" /></template>
