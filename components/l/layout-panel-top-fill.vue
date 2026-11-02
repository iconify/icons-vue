<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fmp4lrb4a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fmp4lrb4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:layout-panel-top-fill" /></template>
