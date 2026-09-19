<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qkymyjbue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qkymyjbue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:arrow-data-transfer-vertical" /></template>
