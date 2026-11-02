<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t6bb_nbyk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t6bb_nbyk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:clock-4-fill" /></template>
