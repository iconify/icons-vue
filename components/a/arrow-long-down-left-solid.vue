<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/trphc0u7f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="trphc0u7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:arrow-long-down-left-solid" /></template>
