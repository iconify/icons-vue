<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sum6q9b1b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sum6q9b1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:ludwig" /></template>
