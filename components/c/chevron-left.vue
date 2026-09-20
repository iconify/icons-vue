<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x5dqhbb4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x5dqhbb4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:chevron-left" /></template>
