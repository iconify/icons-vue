<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rxb_82bqe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rxb_82bqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:lipstick-line" /></template>
