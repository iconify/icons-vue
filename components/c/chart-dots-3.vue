<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l27my8epx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l27my8epx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:chart-dots-3" /></template>
