<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nakui0b-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nakui0b-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:code-octagon-solid" /></template>
