<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lcy26lbin.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lcy26lbin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:hourglass-solid" /></template>
