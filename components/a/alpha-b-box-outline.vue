<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ac78f_lkq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ac78f_lkq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:alpha-b-box-outline" /></template>
