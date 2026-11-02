<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jj_3tub_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jj_3tub_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:arrow-down-fill" /></template>
