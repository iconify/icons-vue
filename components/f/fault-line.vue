<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/upi7cjb6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="upi7cjb6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:fault-line" /></template>
