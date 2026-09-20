<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ljgagpbli.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ljgagpbli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-h-hexagon-solid" /></template>
