<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wd0oxcbug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wd0oxcbug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:dots-fill" /></template>
