<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/krvxqbb_b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="krvxqbb_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:arrow-big-up" /></template>
