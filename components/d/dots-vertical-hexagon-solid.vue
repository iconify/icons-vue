<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e3re1va3n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e3re1va3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:dots-vertical-hexagon-solid" /></template>
