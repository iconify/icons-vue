<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cy4h5kkpm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cy4h5kkpm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:calendar-minus" /></template>
