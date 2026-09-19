<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jvn6v2bbz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jvn6v2bbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:17-track" /></template>
