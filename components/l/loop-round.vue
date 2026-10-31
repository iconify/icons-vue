<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/itx63nyal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="itx63nyal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:loop-round" /></template>
