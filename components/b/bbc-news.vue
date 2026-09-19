<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eqtupxbwh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eqtupxbwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:bbc-news" /></template>
