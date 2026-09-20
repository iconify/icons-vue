<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y4jj9-bcf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y4jj9-bcf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:confetti" /></template>
