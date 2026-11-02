<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bymq2-bbv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bymq2-bbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:car-window-line" /></template>
