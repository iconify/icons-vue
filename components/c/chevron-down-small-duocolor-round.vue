<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r51w4ibnc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r51w4ibnc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chevron-down-small-duocolor-round" /></template>
