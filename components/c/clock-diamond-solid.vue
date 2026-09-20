<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jtn7h2b2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jtn7h2b2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:clock-diamond-solid" /></template>
