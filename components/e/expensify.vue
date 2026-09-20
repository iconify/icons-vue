<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xw0enn4mt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xw0enn4mt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:expensify" /></template>
