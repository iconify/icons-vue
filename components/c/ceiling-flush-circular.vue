<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/klk31e80v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="klk31e80v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:ceiling-flush-circular" /></template>
