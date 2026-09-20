<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xhiqf8q1b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xhiqf8q1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:chart-line-down-sharp" /></template>
