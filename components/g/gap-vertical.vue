<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ds2tvwbin.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ds2tvwbin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:gap-vertical" /></template>
