<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gngs7_bjr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gngs7_bjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:globe-line" /></template>
