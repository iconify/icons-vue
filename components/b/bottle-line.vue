<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c59wd2bpx.css';
import '../../css/m/m6cog7b_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c59wd2bpx"/><path class="m6cog7b_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:bottle-line" /></template>
