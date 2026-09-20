<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sj_jlubrr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sj_jlubrr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:brush-2-fill" /></template>
