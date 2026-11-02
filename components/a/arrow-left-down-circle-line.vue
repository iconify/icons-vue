<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/abmc4lbzt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="abmc4lbzt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:arrow-left-down-circle-line" /></template>
