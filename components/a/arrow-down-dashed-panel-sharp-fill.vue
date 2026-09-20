<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ls-7v03zr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ls-7v03zr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-down-dashed-panel-sharp-fill" /></template>
