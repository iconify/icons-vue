<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aza5olbsu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aza5olbsu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:food-apple-core" /></template>
