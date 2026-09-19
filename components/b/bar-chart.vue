<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z90c49l7l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z90c49l7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:bar-chart" /></template>
