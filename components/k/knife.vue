<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l6vo4rmrq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l6vo4rmrq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:knife" /></template>
