<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/txu3124of.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="txu3124of"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:git-compare-2-line" /></template>
