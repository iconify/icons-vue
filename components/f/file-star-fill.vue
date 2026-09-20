<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lqx6e0bcd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lqx6e0bcd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:file-star-fill" /></template>
