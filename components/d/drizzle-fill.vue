<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k4ny07b_a.css';
import '../../css/s/s0er2727y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k4ny07b_a"/><path class="s0er2727y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:drizzle-fill" /></template>
