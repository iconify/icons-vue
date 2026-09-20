<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r-25xw8du.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r-25xw8du"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:history-fill" /></template>
