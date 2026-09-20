<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dytu10dqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dytu10dqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:battery-vertical-exclamation" /></template>
