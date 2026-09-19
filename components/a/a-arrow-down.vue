<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yddqc0brq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yddqc0brq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:a-arrow-down" /></template>
