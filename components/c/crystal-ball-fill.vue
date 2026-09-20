<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rhyy_4bdf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rhyy_4bdf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:crystal-ball-fill" /></template>
