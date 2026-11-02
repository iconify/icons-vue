<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pfyk8p-da.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pfyk8p-da"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:ins-line" /></template>
