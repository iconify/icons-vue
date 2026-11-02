<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/haimgbp7f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="haimgbp7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:heading-1-fill" /></template>
