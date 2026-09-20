<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i58585-uj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i58585-uj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:annoyed-square" /></template>
