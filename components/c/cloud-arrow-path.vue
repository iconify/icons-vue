<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fo81tgn7q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fo81tgn7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:cloud-arrow-path" /></template>
