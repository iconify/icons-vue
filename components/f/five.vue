<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nycy85bic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nycy85bic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:five" /></template>
