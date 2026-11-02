<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l4f6-z6ya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l4f6-z6ya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:hammer-2-line" /></template>
