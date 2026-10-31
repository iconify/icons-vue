<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tyjunpvwq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tyjunpvwq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:clock-4-fill-round" /></template>
