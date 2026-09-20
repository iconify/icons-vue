<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a_5d7pbjr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a_5d7pbjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:layout-7-line" /></template>
