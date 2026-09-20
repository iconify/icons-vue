<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ep5a_vvsv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ep5a_vvsv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:link-two" /></template>
