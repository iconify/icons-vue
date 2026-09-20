<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z5jly29gn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z5jly29gn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bar-chart-2" /></template>
