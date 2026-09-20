<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iadd8ybpx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iadd8ybpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:arrow-right-waves-solid" /></template>
