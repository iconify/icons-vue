<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xgcz08qqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xgcz08qqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:book-open" /></template>
