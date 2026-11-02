<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/caiskpovg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="caiskpovg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:beef-off-line" /></template>
