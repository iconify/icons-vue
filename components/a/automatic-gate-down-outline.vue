<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jz9uo7bkq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jz9uo7bkq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:automatic-gate-down-outline" /></template>
