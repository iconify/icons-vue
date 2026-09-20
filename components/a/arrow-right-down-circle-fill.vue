<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n17e6j3vn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n17e6j3vn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:arrow-right-down-circle-fill" /></template>
